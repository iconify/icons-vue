<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy2gdub1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sy2gdub1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-slash" /></template>
