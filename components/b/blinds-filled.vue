<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stdr-7bvd.css';
import '../../css/z/zt9l85bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stdr-7bvd"/><path class="zt9l85bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:blinds-filled" /></template>
