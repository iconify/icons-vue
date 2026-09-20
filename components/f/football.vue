<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn35t7a4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn35t7a4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:football" /></template>
