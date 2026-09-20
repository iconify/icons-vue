<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq-5xlbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:circles-ext-outline-rounded" /></template>
<style>
.wq-5xlbai {
  fill: currentColor;
  d: path("M3.714 19.287q-.945-.945-.945-2.287t.944-2.286T6 13.769t2.286.944T9.232 17t-.944 2.286T6 20.232t-2.286-.945m12 0q-.945-.944-.945-2.286t.944-2.286T18 13.769t2.286.944t.945 2.287t-.945 2.286t-2.286.945t-2.286-.945M6 19.232q.921 0 1.576-.655T8.231 17t-.655-1.576T6 14.769t-1.576.655T3.769 17t.655 1.576T6 19.231m12 0q.921 0 1.576-.655T20.231 17t-.655-1.576T18 14.769t-1.576.655T15.769 17t.655 1.576t1.576.655m-7.071-5.16q-.444-.444-.444-1.071t.444-1.071T12 11.485t1.071.444t.445 1.071t-.445 1.071t-1.071.445t-1.071-.445M9.714 8.287Q8.769 7.342 8.769 6t.944-2.286T12 2.769t2.286.945T15.232 6t-.944 2.286T12 9.232t-2.286-.944m3.862-.711q.655-.655.655-1.576t-.655-1.576T12 3.769t-1.576.655T9.769 6t.655 1.576T12 8.231t1.576-.655M18 17");
}

</style>
