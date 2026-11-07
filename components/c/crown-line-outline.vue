<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvamu-4ox.css';
import '../../css/c/c_eh8tc1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvamu-4ox"/><path clip-rule="evenodd" class="c_eh8tc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-line-outline" /></template>
