<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aho8tg6fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aho8tg6fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:child-care" /></template>
