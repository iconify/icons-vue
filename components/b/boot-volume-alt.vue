<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x93jqtbel.css';
import '../../css/w/wk2d_zbto.css';
import '../../css/n/nc-ntg30u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x93jqtbel"/><path class="wk2d_zbto"/><path class="nc-ntg30u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:boot-volume-alt" /></template>
