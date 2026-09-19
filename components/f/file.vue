<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1we_sbru.css';
import '../../css/w/wo3zs2b-t.css';
import '../../css/j/j06su1bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a1we_sbru"/><path class="wo3zs2b-t"/><path class="j06su1bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:file" /></template>
