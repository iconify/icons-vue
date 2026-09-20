<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blxgbnb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blxgbnb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-open" /></template>
