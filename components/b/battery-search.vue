<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpgjzfkqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:battery-search" /></template>
<style>
.vpgjzfkqa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 3.25H6q-1.76 0-3.005 1.245T1.75 7.5V12q0 1.76 1.245 3.005T6 16.25h5.005q.084-1.91 1.459-3.286Q13.929 11.5 16 11.5t3.536 1.464q.251.252.46.522q.172-.469.228-.986h.276q1.75 0 1.75-1.75v-2Q22.25 7 20.5 7h-.276q-.155-1.441-1.219-2.505Q17.76 3.25 16 3.25M20.5 11h-.25V8.5h.25q.25 0 .25.25v2q0 .25-.25.25M16 12.75q-3.75 0-3.75 3.75T16 20.25q1.345 0 2.207-.482l2.263 2.262q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-2.262-2.263q.482-.862.482-2.207q0-3.75-3.75-3.75m0 6q-2.25 0-2.25-2.25T16 14.25t2.25 2.25T16 18.75m0-2.5q.502 0 .962-.101q-.157-.649-.962-.649q-.866 0-.982.75z");
}

</style>
