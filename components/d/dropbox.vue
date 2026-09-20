<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6ffl6b-d.css';
import '../../css/c/czuc2kb0l.css';
import '../../css/b/bphnj6bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6ffl6b-d"/><path clip-rule="evenodd" class="czuc2kb0l"/><path clip-rule="evenodd" class="bphnj6bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:dropbox" /></template>
