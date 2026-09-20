<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2ng3jt7l.css';
import '../../css/j/j6bkybbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2ng3jt7l"/><path class="j6bkybbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cog" /></template>
