<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ennyb0i.css';
import '../../css/n/n5rw468eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ennyb0i"/><path class="n5rw468eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-square-filled" /></template>
