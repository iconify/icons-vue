<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gav6n2baw.css';
import '../../css/b/bl21z0b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="gav6n2baw"/><path class="bl21z0b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:alert" /></template>
