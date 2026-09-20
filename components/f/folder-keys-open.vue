<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpc9hgrvp.css';
import '../../css/i/iywcnqb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mpc9hgrvp"/><path class="iywcnqb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-keys-open" /></template>
