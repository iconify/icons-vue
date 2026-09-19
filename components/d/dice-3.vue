<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm5btrboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pm5btrboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:dice-3" /></template>
