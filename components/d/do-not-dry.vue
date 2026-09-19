<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cua6mti1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":512};
const content = `<path class="cua6mti1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:do-not-dry" /></template>
