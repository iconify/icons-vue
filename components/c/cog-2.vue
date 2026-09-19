<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtrqn2bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtrqn2bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:cog-2" /></template>
