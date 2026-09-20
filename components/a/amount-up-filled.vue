<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo4yz7b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lo4yz7b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-up-filled" /></template>
