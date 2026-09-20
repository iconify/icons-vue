<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mne6x2b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mne6x2b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banknote" /></template>
