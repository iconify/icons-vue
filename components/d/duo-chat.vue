<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0l3ckbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c0l3ckbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:duo-chat" /></template>
