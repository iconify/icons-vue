<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cup6pv9rx.css';
import '../../css/j/j11y15vpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cup6pv9rx"/><path class="j11y15vpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-image-fill-20" /></template>
