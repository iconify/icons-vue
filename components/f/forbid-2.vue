<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlr-l1vuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlr-l1vuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:forbid-2" /></template>
