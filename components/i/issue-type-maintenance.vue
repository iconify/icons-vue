<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0khhdbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0khhdbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-maintenance" /></template>
