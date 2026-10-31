<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg80gw99l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg80gw99l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk" /></template>
