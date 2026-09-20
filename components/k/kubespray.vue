<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztgb-ac9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztgb-ac9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kubespray" /></template>
