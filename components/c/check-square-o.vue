<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwt7dmi2n.css';
import '../../css/c/c8k9rbbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwt7dmi2n"/><path class="c8k9rbbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:check-square-o" /></template>
