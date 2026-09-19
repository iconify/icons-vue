<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn1mi4dfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jn1mi4dfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:ear" /></template>
