<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv7ro-bzc.css';
import '../../css/l/lru0_snsm.css';
import '../../css/t/tqgpg9bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv7ro-bzc"/><path class="lru0_snsm"/><path class="tqgpg9bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fish-off-filled" /></template>
