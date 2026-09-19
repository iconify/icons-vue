<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2wh_732m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k2wh_732m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:capsule" /></template>
