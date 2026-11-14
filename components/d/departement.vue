<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnmv6cwab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnmv6cwab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:departement" /></template>
