<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prrqvyblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prrqvyblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-keyhole-open-alt-filled" /></template>
