<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8bdc-bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8bdc-bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lock-semi-open" /></template>
