<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i14yeqg2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i14yeqg2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dotproject" /></template>
