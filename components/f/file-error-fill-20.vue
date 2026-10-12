<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o72q1jmah.css';
import '../../css/j/j11y15vpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o72q1jmah"/><path class="j11y15vpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-error-fill-20" /></template>
