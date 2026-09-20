<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ems_ytbdz.css';
import '../../css/x/xwn1thb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ems_ytbdz"/><path clip-rule="evenodd" class="xwn1thb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:laravel-solid" /></template>
