<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awlbw9bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="awlbw9bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:floppy-disk" /></template>
