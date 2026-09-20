<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2v1743-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2v1743-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock-keyhole-open-filled" /></template>
