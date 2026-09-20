<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smlsjm9jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smlsjm9jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:h6-solid" /></template>
