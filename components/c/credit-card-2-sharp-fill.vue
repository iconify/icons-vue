<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x188g-mka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x188g-mka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-2-sharp-fill" /></template>
