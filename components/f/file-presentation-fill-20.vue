<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwwerab1t.css';
import '../../css/j/j11y15vpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cwwerab1t"/><path class="j11y15vpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-presentation-fill-20" /></template>
