<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf9770bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf9770bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-2" /></template>
