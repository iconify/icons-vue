<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0qf9mgcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compostable-bag" /></template>
<style>
.t0qf9mgcs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 22.25q-2.75 0-2.75-2.75q0-6.238 6.273-10.276L7.329 4.835q-.039-.078-.059-.163T7.25 4.5t.02-.172t.059-.163q.067-.134.18-.232q.112-.097.254-.145q.141-.047.29-.036q.149.01.282.077L12 5.661l3.665-1.832q.078-.039.163-.059T16 3.75t.172.02t.163.059q.134.067.232.18q.097.112.145.254q.047.141.036.29q-.01.149-.077.282l-2.194 4.389Q20.75 13.262 20.75 19.5q0 2.75-2.75 2.75zm2.75-3.751v.001q0 .141.051.272t.146.235l.023.023q.105.106.243.163t.287.057h.001q5.749 0 5.749-5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14.5 13q-5.749 0-5.75 5.499");
}

</style>
