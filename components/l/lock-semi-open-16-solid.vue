<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcrxfd7um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dcrxfd7um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lock-semi-open-16-solid" /></template>
