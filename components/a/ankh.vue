<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhdgvnbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhdgvnbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ankh" /></template>
