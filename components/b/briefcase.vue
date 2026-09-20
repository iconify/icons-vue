<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rhsn0wbko"/><path class="ztuy1v-kr"/><path class="sg_70qblk"/><path class="bg6jcfbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:briefcase" /></template>
<style>
.bg6jcfbfn {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M22 18a2 2 0 0 1-2 2h-4a2 2 0 0 1 0-4h4a2 2 0 0 1 2 2");
}

.rhsn0wbko {
  fill: var(--svg-color--9a4e1c, #9a4e1c);
  d: path("M32 8h-6V4a4 4 0 0 0-4-4h-8a4 4 0 0 0-4 4v4H4a4 4 0 0 0-4 4v20a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V12a4 4 0 0 0-4-4M12 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v2H12z");
}

.sg_70qblk {
  fill: var(--svg-color--9a4e1c, #9a4e1c);
  d: path("M36 18a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-6a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.ztuy1v-kr {
  fill: var(--svg-color--662113, #662113);
  d: path("M36 20a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-8a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
