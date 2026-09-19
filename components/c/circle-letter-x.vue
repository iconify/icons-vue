<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqs_9jtvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pqs_9jtvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-x" /></template>
