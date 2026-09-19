<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz2vv8csr.css';
import '../../css/z/z0s8mnbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz2vv8csr"/><path class="z0s8mnbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-narrow-wide-filled" /></template>
