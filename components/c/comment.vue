<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnw4fjboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jnw4fjboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:comment" /></template>
