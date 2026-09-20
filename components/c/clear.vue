<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3gzm8rrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n3gzm8rrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:clear" /></template>
