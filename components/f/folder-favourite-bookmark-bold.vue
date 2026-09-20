<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy7r9nb-t.css';
import '../../css/g/gfq35jb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7r9nb-t"/><path class="gfq35jb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-favourite-bookmark-bold" /></template>
