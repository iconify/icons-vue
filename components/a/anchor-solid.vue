<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaeqwrb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaeqwrb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:anchor-solid" /></template>
