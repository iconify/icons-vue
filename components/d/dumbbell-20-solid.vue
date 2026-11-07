<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1it2bcqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f1it2bcqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dumbbell-20-solid" /></template>
