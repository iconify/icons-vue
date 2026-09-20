<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euneofz2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euneofz2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:down-left-fill" /></template>
