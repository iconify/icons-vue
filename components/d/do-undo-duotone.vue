<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibopftbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibopftbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-undo-duotone" /></template>
