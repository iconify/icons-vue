<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7oerkp_t.css';
import '../../css/j/j11y15vpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b7oerkp_t"/><path class="j11y15vpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-document-fill-20" /></template>
