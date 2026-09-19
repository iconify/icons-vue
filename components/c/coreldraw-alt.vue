<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2_ie9n9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":371,"height":512};
const content = `<path clip-rule="evenodd" class="b2_ie9n9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:coreldraw-alt" /></template>
