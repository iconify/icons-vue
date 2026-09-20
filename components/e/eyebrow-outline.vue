<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snl1nb8ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eyebrow-outline" /></template>
<style>
.snl1nb8ua {
  fill: currentColor;
  d: path("M14.923 13.558q-1.048 0-2.18.176q-1.132.177-2.347.485t-2.514.721t-2.674.893q-.256.086-.495.126q-.24.041-.463.041q-1.026 0-1.743-.663q-.718-.664-.718-1.587v-2.267q0-.805.559-1.431q.56-.627 1.418-.77q1.739-.305 3.358-.544t3.036-.402t2.631-.25Q14.006 8 14.942 8q2.966 0 4.88 1.949q1.915 1.949 2.376 5.436q.03.16-.07.285q-.1.126-.26.196q-.147.07-.302.05q-.156-.022-.316-.145q-1.523-1-3.294-1.607t-3.033-.606m0-1q1.235 0 2.673.43q1.439.43 3.356 1.404q-.633-2.679-2.145-4.035T14.923 9q-1.952 0-4.917.342q-2.966.342-6.033.916q-.518.094-.851.44q-.334.345-.334.785v2.267q0 .666.65 1.03q.648.364 1.398.107q1.577-.53 2.95-.961t2.597-.733q1.223-.3 2.343-.468t2.197-.167m-3.056-1.075");
}

</style>
