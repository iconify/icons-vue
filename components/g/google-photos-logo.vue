<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7t_4ffnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7t_4ffnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-photos-logo" /></template>
