<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5ul61b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s5ul61b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-grin-beam" /></template>
