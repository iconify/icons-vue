<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h149-xhjx.css';
import '../../css/e/esvqany8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="h149-xhjx"/><path class="esvqany8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:angle-double-right" /></template>
