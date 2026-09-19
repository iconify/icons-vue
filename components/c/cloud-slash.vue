<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g77ie7akg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g77ie7akg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:cloud-slash" /></template>
