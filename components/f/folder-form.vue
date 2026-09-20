<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ad0g2qb.css';
import '../../css/y/ykiyg6-he.css';
import '../../css/q/qgl6-9-os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-ad0g2qb"/><path class="ykiyg6-he"/><path class="qgl6-9-os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-form" /></template>
