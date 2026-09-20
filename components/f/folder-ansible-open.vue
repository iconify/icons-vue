<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnxr3dbjd.css';
import '../../css/n/no6ore_5j.css';
import '../../css/q/qlk7i1b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bnxr3dbjd"/><path class="no6ore_5j"/><path class="qlk7i1b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-ansible-open" /></template>
