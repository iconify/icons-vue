<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uet_h9nyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uet_h9nyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:css" /></template>
