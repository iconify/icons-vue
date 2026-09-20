<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__nckb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="b__nckb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:airplanetakeoff" /></template>
