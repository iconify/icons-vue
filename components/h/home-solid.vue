<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro-ic_bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-ic_bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:home-solid" /></template>
