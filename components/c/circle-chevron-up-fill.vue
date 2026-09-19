<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii0ewyw5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ii0ewyw5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevron-up-fill" /></template>
