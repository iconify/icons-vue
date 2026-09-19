<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkz6xik2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gkz6xik2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:chevrons-expand-to-lines" /></template>
