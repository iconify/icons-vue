<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-e4ckbto.css';
import '../../css/b/birgbmbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-e4ckbto"/><path clip-rule="evenodd" class="birgbmbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:file-manager-16" /></template>
