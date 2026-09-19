<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x974jcb9h.css';
import '../../css/w/w6uyb-bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x974jcb9h"/><path class="w6uyb-bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bullhorn-solid" /></template>
