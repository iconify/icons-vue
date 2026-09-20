<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxt1u-fiz.css';
import '../../css/q/qoxo-5byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxt1u-fiz"/><path class="qoxo-5byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-classical-24" /></template>
