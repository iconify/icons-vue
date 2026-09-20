<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sntqev2mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sntqev2mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:inner-shadow-left-filled" /></template>
