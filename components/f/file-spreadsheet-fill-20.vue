<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4snd7u8p.css';
import '../../css/j/j11y15vpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v4snd7u8p"/><path class="j11y15vpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-spreadsheet-fill-20" /></template>
