<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5n4_s5eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b5n4_s5eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-right" /></template>
