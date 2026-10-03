<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vcy18cbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-packship" /></template>
<style>
.vcy18cbqh {
  fill: var(--svg-color--3f3d56, #3f3d56);
  d: path("M12.98 19.39q-.5.02-.7-.25q-.23-.3-.14-.9q.1-.53.27-.8t.64-.32q3.26-.18 4.92-1.04q2.2-.86 3.76-2.2q1.59-1.36 2.43-3.04q.86-1.72.84-3.6q0-1.48-.69-2.2q-.68-.77-1.94-.77q-1.12 0-2.34.59q-1.27.63-2.5 1.65q-1.2 1.07-2.37 2.56q-1.14 1.48-2.16 3.3q-.97 1.8-1.72 3.85l-4.22 13q-.13.42-.43.58q-.32.2-.95.2q-.6 0-.9-.2q-.28-.2-.17-.62l7.03-21.63q-.68.68-1.43 1.32t-1.6 1.25l-1.75 1.24q-.57.39-.95.25t-.68-.63Q5 10.57 5 10.16q.07-.4.59-.7q1.58-1 2.95-2.04q1.4-1.07 2.53-2.2q1.14-1.18 2-2.43q.32-.38.59-.63q.27-.16.86-.16q.64 0 .9.18q.3.2.14.64l-1.4 4.49q1.24-1.68 2.63-2.88q1.43-1.2 2.88-1.82Q21.17 2 22.66 2q1.47 0 2.54.59q1.09.61 1.65 1.7q.57 1.07.57 2.58q0 2.57-1.06 4.77q-1.05 2.17-3.02 3.85q-1.95 1.66-4.58 2.58q-1.88.64-5.76 1.2z");
}

</style>
