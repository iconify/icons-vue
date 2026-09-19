<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beu4rcn5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="beu4rcn5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:decrease-indent" /></template>
