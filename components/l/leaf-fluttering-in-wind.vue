<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8t-vbbi.css';
import '../../css/b/b_slk7bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tj8t-vbbi"/><path class="b_slk7bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leaf-fluttering-in-wind" /></template>
