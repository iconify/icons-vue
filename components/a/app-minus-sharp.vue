<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug_mu57hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug_mu57hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-minus-sharp" /></template>
