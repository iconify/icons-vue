<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_aaylb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b_aaylb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eye-slash-fill" /></template>
