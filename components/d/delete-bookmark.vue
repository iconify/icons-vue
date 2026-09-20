<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7y5wkl1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7y5wkl1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:delete-bookmark" /></template>
