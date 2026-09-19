<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu5nodbov.css';
import '../../css/w/wu_mdhb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu5nodbov"/><path class="wu_mdhb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:black-lives-matter" /></template>
