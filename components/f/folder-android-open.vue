<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8rt5bbrs.css';
import '../../css/k/kilgsnbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8rt5bbrs"/><path class="kilgsnbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-android-open" /></template>
