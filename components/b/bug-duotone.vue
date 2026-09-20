<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmmio3p-i.css';
import '../../css/w/w7niv3b6v.css';
import '../../css/c/c76r55w5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmmio3p-i"/><path class="w7niv3b6v"/><path class="c76r55w5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:bug-duotone" /></template>
