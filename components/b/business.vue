<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5w07jbzw.css';
import '../../css/f/f30po-b8i.css';
import '../../css/c/c6en_42bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5w07jbzw"/><path class="f30po-b8i"/><path class="c6en_42bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:business" /></template>
