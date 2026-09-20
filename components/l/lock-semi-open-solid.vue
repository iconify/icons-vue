<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjcfnu1xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjcfnu1xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lock-semi-open-solid" /></template>
