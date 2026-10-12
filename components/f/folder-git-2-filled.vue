<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onjqb9blp.css';
import '../../css/g/g3refjfpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onjqb9blp"/><path class="g3refjfpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-git-2-filled" /></template>
