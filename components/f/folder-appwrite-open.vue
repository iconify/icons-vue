<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-td7-p-y.css';
import '../../css/i/iz42m8brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-td7-p-y"/><path class="iz42m8brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-appwrite-open" /></template>
