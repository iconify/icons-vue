<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbmn2oygh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":9,"height":16};
const content = `<path class="zbmn2oygh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:caretright" /></template>
