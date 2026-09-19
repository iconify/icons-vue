<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_e9v2bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b_e9v2bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:eye-slash" /></template>
