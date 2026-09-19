<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9b-07nxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a9b-07nxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:lightning-circle-filled" /></template>
