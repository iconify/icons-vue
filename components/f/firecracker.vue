<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ejiblrb9w.css';
import '../../css/a/azrmef7ww.css';
import '../../css/t/thw7gsbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ejiblrb9w"/><path class="azrmef7ww"/><path class="thw7gsbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:firecracker" /></template>
