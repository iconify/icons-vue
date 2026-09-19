<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3pk7wb9n.css';
import '../../css/d/d325_0h8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3pk7wb9n"/><path class="d325_0h8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-wide-narrow-filled" /></template>
