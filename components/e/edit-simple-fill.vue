<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-k_phixn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-k_phixn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:edit-simple-fill" /></template>
