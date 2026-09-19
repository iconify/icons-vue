<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv6xttbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="lv6xttbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:colors" /></template>
