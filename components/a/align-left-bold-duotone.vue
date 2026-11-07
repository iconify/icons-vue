<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpvo_gb0n.css';
import '../../css/a/akoivubxv.css';
import '../../css/e/eqwsh3bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpvo_gb0n"/><path class="akoivubxv"/><path clip-rule="evenodd" class="eqwsh3bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-bold-duotone" /></template>
