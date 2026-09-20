<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gex-ugb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gex-ugb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:diners-club" /></template>
