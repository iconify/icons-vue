<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq5mbxbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iq5mbxbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cpanel" /></template>
