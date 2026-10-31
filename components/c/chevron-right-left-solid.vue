<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqd2iu2hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eqd2iu2hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-right-left-solid" /></template>
