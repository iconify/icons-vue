<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oswg-4fqg.css';
import '../../css/e/eqbv84bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oswg-4fqg"/><path clip-rule="evenodd" class="eqbv84bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:file-script-16" /></template>
