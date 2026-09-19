<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4_6zfl5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4_6zfl5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lotion" /></template>
