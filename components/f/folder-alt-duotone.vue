<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmytx2b1a.css';
import '../../css/g/gox9jubaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmytx2b1a"/><path clip-rule="evenodd" class="gox9jubaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-alt-duotone" /></template>
