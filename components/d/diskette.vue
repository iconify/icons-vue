<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5bp7pmdg.css';
import '../../css/z/z5-9hkvso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l5bp7pmdg"/><path class="z5-9hkvso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:diskette" /></template>
