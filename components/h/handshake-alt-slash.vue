<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkgh3ntpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="nkgh3ntpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:handshake-alt-slash" /></template>
