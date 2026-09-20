<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/go52lxd2s.css';
import '../../css/a/a-tw77iau.css';
import '../../css/i/ispua1bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="go52lxd2s"/><path class="a-tw77iau"/><path class="ispua1bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:checkmark-outlined" /></template>
